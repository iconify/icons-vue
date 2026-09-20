<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks-6myb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks-6myb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:trending-up-duotone" /></template>
