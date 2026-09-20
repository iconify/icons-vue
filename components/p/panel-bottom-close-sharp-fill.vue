<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjm4x02vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjm4x02vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-bottom-close-sharp-fill" /></template>
