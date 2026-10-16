<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgvqv2bst.css';
import '../../css/v/vtc-cfb1t.css';
import '../../css/k/ka-2hq9em.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dgvqv2bst"/><path class="vtc-cfb1t"/><path class="ka-2hq9em"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tokamak-20" /></template>
