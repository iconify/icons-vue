<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-00eccfu.css';
import '../../css/i/i6o-cqbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w-00eccfu"/><path class="i6o-cqbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:tracked-by-closed-not-planned-16" /></template>
