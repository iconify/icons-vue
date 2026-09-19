<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7ifnpa_v.css';
import '../../css/c/cqaf674jx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="f7ifnpa_v"/><path class="cqaf674jx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:wasp" /></template>
