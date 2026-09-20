<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggf2lacfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggf2lacfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-received-fill" /></template>
