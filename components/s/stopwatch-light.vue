<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c42wbbbmv.css';
import '../../css/a/a9mdu8gjb.css';
import '../../css/u/upbnhsbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c42wbbbmv"/><path class="a9mdu8gjb"/><path clip-rule="evenodd" class="upbnhsbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:stopwatch-light" /></template>
