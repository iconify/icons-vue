<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp_ezhbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rp_ezhbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:meet-and-greet" /></template>
