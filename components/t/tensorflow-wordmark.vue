<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqrtldgzg.css';
import '../../css/p/p5kyztbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gqrtldgzg"/><path class="p5kyztbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:tensorflow-wordmark" /></template>
