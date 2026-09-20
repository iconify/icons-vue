<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sokgaqver.css';
import '../../css/x/xnv-09bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sokgaqver"/><path class="xnv-09bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:sign-in" /></template>
