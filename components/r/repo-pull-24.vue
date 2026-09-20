<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceknmg57b.css';
import '../../css/a/agohndbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ceknmg57b"/><path class="agohndbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-pull-24" /></template>
