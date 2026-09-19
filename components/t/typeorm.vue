<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky_82sbmu.css';
import '../../css/o/okeacwbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ky_82sbmu"/><path class="okeacwbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:typeorm" /></template>
