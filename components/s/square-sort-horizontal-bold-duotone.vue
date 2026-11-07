<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edf2mabxb.css';
import '../../css/t/tmi2ocbvf.css';
import '../../css/r/rwz9xbcdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edf2mabxb"/><path class="tmi2ocbvf"/><path class="rwz9xbcdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-sort-horizontal-bold-duotone" /></template>
