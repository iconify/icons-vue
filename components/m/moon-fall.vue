<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezyw46bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezyw46bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:moon-fall" /></template>
