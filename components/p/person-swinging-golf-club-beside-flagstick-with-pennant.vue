<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q14_dk0ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q14_dk0ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-swinging-golf-club-beside-flagstick-with-pennant" /></template>
