<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1dbcvb1r.css';
import '../../css/y/yiwa8gb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x1dbcvb1r"/><path class="yiwa8gb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:shapes-outline" /></template>
