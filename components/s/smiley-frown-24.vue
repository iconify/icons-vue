<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldiu6s_fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldiu6s_fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:smiley-frown-24" /></template>
