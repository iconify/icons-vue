<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijssdnbls.css';
import '../../css/m/m6zv5vbnf.css';
import '../../css/j/jqr1k9a2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijssdnbls"/><path class="m6zv5vbnf"/><path class="jqr1k9a2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smart-speaker-2-bold" /></template>
