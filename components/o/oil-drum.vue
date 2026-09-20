<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy4f4tdmp.css';
import '../../css/d/di45v_bru.css';
import '../../css/b/bzswb8b6a.css';
import '../../css/d/d2db97k3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="uy4f4tdmp"/><path class="di45v_bru"/><path class="bzswb8b6a"/><path class="d2db97k3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:oil-drum" /></template>
