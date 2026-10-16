<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k989r-bis.css';
import '../../css/l/lr8gvf09r.css';
import '../../css/j/jxg5-_o0q.css';
import '../../css/f/fkgyoyhzs.css';
import '../../css/v/vdh35hb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k989r-bis"/><path class="lr8gvf09r"/><path class="jxg5-_o0q"/><path class="fkgyoyhzs"/><path class="vdh35hb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pv-string-48" /></template>
