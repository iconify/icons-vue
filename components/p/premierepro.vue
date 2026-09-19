<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_om5egbx.css';
import '../../css/a/aucylab8w.css';
import '../../css/p/pimz7_f2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="v_om5egbx"/><path class="aucylab8w"/><path class="pimz7_f2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:premierepro" /></template>
