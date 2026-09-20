<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5b76tsta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5b76tsta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-stop-sharp" /></template>
