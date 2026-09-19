<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2o2k5bfa.css';
import '../../css/e/eafmg15uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e2o2k5bfa"/><path class="eafmg15uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:picture-rounded" /></template>
