<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn2-zcb5a.css';
import '../../css/h/hx140-n7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="fn2-zcb5a"/><path class="hx140-n7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yubal" /></template>
