<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu2l__qdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lu2l__qdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:phonecall-blocked-outline" /></template>
