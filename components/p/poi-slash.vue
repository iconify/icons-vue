<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7pghdblc.css';
import '../../css/w/wu7dgpbsv.css';
import '../../css/b/b2tobl9de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="l7pghdblc"/><path class="wu7dgpbsv"/><path class="b2tobl9de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:poi-slash" /></template>
