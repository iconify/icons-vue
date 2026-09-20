<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/outf-abwk.css';
import '../../css/g/gd4eslbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="outf-abwk"/><path class="gd4eslbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:mailbox-empty-light" /></template>
