<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwxd6gr7h.css';
import '../../css/g/g-drd0b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bwxd6gr7h"/><path class="g-drd0b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:quasar" /></template>
