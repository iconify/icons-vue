<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um39my9-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um39my9-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:mirror-24" /></template>
