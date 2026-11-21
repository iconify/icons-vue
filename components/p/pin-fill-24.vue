<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5kl9907t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5kl9907t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:pin-fill-24" /></template>
