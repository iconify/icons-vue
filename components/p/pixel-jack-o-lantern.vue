<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm_61uztw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nm_61uztw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-jack-o-lantern" /></template>
