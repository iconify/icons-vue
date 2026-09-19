<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsle34bel.css';
import '../../css/e/e24p9ccpg.css';
import '../../css/j/j3k06lbcb.css';
import '../../css/o/o6419p7rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hsle34bel"/><path class="e24p9ccpg"/><path class="j3k06lbcb"/><path class="o6419p7rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:materialui" /></template>
