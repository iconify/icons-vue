<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbsw-ac5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbsw-ac5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:shopping-cart-fill" /></template>
