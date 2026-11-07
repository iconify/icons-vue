<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti6p48bml.css';
import '../../css/a/ahs3192tr.css';
import '../../css/o/ortpaq31n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti6p48bml"/><path class="ahs3192tr"/><path class="ortpaq31n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-cross-bold" /></template>
