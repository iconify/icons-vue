<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtl2x5b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtl2x5b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pin-02" /></template>
