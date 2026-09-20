<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvibj51bk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-2.5};
const content = `<path class="pvibj51bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:pin-f" /></template>
