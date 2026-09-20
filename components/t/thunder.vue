<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqdup5oyd.css';
import '../../css/a/a3yzckbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bqdup5oyd"/><path class="a3yzckbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:thunder" /></template>
