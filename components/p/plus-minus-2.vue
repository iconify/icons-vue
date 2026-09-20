<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzwie_b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzwie_b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:plus-minus-2" /></template>
