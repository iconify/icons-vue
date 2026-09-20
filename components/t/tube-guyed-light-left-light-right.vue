<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5d2v1bhr.css';
import '../../css/u/ui-ri_b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v5d2v1bhr"/><path class="ui-ri_b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:tube-guyed-light-left-light-right" /></template>
