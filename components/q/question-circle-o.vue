<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6_537x8t.css';
import '../../css/v/vd_9zuben.css';
import '../../css/s/ss70euapj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f6_537x8t"/><path class="vd_9zuben"/><path class="ss70euapj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:question-circle-o" /></template>
