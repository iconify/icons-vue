<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmy7obc7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmy7obc7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:twinkly-candies-pearl" /></template>
