<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/r/r86azabhr.css';
import '../../css/g/gidh62bnp.css';
import '../../css/b/blfr88bmm.css';
import '../../css/e/eb2rtqbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="r86azabhr wm-shadow"/><path class="gidh62bnp wm-shadow"/><path class="blfr88bmm"/><path class="eb2rtqbzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:tv" /></template>
