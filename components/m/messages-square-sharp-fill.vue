<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix1u1i3gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix1u1i3gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:messages-square-sharp-fill" /></template>
