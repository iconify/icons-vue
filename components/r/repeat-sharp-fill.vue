<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcxeqn1hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcxeqn1hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:repeat-sharp-fill" /></template>
