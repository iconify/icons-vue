<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5o67xb4n.css';
import '../../css/v/vclaoe-gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="v5o67xb4n"/><path class="vclaoe-gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vlang" /></template>
