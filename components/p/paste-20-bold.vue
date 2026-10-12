<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0ne4_zha.css';
import '../../css/a/appx2gb4r.css';
import '../../css/e/em0ki7-fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k0ne4_zha"/><path class="appx2gb4r"/><path class="em0ki7-fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paste-20-bold" /></template>
