<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo8x__b5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo8x__b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:maps" /></template>
