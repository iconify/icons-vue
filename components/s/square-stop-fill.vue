<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eedmefb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eedmefb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-stop-fill" /></template>
