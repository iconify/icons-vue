<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhplk3b6j.css';
import '../../css/e/ehu_tqb0a.css';
import '../../css/q/qghyp15aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vhplk3b6j"/><path class="ehu_tqb0a"/><path class="qghyp15aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:mobile" /></template>
