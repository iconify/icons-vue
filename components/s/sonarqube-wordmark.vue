<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5wleyipv.css';
import '../../css/u/uxlky7uhp.css';
import '../../css/c/cq11jcb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n5wleyipv"/><path class="uxlky7uhp"/><path class="cq11jcb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sonarqube-wordmark" /></template>
