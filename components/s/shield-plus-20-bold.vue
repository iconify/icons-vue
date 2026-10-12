<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gglz27bws.css';
import '../../css/b/btfpme1ph.css';
import '../../css/u/udj0ufbcm.css';
import '../../css/v/vn61y3npo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gglz27bws"/><path class="btfpme1ph"/><path class="udj0ufbcm"/><path class="vn61y3npo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-plus-20-bold" /></template>
