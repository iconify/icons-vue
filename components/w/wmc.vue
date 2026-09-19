<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6y36oe8d.css';
import '../../css/b/biue_cm9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="q6y36oe8d"/><path class="biue_cm9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:wmc" /></template>
