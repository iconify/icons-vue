<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k83am1-wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k83am1-wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-shield-filled" /></template>
