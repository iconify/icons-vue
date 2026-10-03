<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abepz8bal.css';
import '../../css/h/h2b5tt5ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="abepz8bal"/><path class="h2b5tt5ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:release-16" /></template>
