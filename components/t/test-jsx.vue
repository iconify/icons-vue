<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nycdyjolw.css';
import '../../css/o/o7pmz67-b.css';
import '../../css/k/k8-ktvkft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nycdyjolw"/><circle class="o7pmz67-b"/><path class="k8-ktvkft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:test-jsx" /></template>
