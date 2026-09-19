<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3huzywhg.css';
import '../../css/a/af8o1jbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h3huzywhg"/><path class="af8o1jbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:shopping-cart-outline" /></template>
