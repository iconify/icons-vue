<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6onf1bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6onf1bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:quote-sharp-fill" /></template>
