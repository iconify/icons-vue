<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m91xfrbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m91xfrbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:sick" /></template>
