<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/g/guntzbbhs.css';
import '../../css/t/tay_8uvgz.css';
import '../../css/o/o8yfolhog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="guntzbbhs"/><path class="tay_8uvgz"/><path class="o8yfolhog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:photo" /></template>
