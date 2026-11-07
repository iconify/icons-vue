<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-4tj5bwa.css';
import '../../css/x/x7-wb_rwz.css';
import '../../css/c/ctjzn5myy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-4tj5bwa"/><path class="x7-wb_rwz"/><path class="ctjzn5myy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-3-bold-duotone" /></template>
