<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq5ia6bva.css';
import '../../css/d/d9j16w-4q.css';
import '../../css/h/ha7cjabon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gq5ia6bva"/><path class="d9j16w-4q"/><path class="ha7cjabon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ubuntu-wordmark" /></template>
