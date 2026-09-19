<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7qt6_goq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7qt6_goq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:windows-legacy" /></template>
