<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/e/eovavrbyd.css';
import '../../css/b/beua1hduq.css';
import '../../css/t/tzalnc8mr.css';
import '../../css/n/nunh1nbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="eovavrbyd"/><path class="beua1hduq"/><path class="tzalnc8mr"/><path class="nunh1nbfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:worldwide-web-sync" /></template>
