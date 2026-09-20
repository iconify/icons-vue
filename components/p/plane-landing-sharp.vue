<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv5m0ubjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv5m0ubjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:plane-landing-sharp" /></template>
