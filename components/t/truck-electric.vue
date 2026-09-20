<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/b/bcij7o89t.css';
import '../../css/y/yuyn37ibu.css';
import '../../css/m/m9nrudbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bcij7o89t"/><circle class="yuyn37ibu"/><circle class="m9nrudbxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:truck-electric" /></template>
