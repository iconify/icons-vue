<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3r5gmb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3r5gmb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:two-finger-02" /></template>
