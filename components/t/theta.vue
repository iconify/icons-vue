<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drv6t-b4e.css';
import '../../css/j/jnwm9c43p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="drv6t-b4e"/><path class="jnwm9c43p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:theta" /></template>
