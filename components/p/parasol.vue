<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5bgb_b8s.css';
import '../../css/c/csm28-9_z.css';
import '../../css/b/bdkeo7bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5bgb_b8s"/><path class="csm28-9_z"/><path class="bdkeo7bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:parasol" /></template>
