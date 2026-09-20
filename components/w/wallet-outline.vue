<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb2wzhlwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fb2wzhlwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:wallet-outline" /></template>
