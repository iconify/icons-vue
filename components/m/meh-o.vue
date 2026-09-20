<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd_9zuben.css';
import '../../css/i/ihffxab9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vd_9zuben"/><path class="ihffxab9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:meh-o" /></template>
