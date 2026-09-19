<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3v4iib0v.css';
import '../../css/m/m364hlh3h.css';
import '../../css/l/l97nb-quh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3v4iib0v"/><path class="m364hlh3h"/><circle class="l97nb-quh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:wifi-2" /></template>
