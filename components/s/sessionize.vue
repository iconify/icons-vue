<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvt9n_7pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvt9n_7pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sessionize" /></template>
