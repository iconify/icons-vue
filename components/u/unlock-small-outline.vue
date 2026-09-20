<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgklwys6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pgklwys6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:unlock-small-outline" /></template>
