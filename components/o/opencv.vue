<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjxsglbxd.css';
import '../../css/b/bmmii1ffg.css';
import '../../css/i/izbfus17g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cjxsglbxd"/><path class="bmmii1ffg"/><path class="izbfus17g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:opencv" /></template>
