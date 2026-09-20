<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1-n19beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1-n19beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:menu-sharp-duotone" /></template>
