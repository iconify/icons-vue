<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buesj7b-t.css';
import '../../css/m/m6ykrib3p.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/s/s28pbybii.css';
import '../../css/e/e2b97rfie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="buesj7b-t"/><path class="m6ykrib3p"/><g class="jn8qy4bru"><path class="s28pbybii"/><path class="e2b97rfie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:two-hump-camel" /></template>
