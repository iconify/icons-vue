<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/bja55jb5m.css';
import '../../css/u/u6ndf9jqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="settings-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="bja55jb5m"/><path class="u6ndf9jqp"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:settings-outline" /></template>
