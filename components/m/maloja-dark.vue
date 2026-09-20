<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnmkpgmsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bnmkpgmsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:maloja-dark" /></template>
