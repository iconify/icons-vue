<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9eo6d69l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9eo6d69l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shopping-basket-02" /></template>
