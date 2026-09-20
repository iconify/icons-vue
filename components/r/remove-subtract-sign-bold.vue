<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spe35eb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="spe35eb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:remove-subtract-sign-bold" /></template>
