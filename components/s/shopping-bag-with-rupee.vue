<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr0d_ccqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fr0d_ccqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-rupee" /></template>
