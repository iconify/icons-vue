<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imt3fu8pc.css';
import '../../css/g/g9wjd3b3c.css';
import '../../css/o/oqnjuob9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imt3fu8pc"/><path class="g9wjd3b3c"/><path class="oqnjuob9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:more-horizontal" /></template>
