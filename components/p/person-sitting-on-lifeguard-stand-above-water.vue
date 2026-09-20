<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2ts7v77x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b2ts7v77x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-sitting-on-lifeguard-stand-above-water" /></template>
