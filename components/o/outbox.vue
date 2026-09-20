<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/intqmzodw.css';
import '../../css/j/jbvtufb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="intqmzodw"/><path class="jbvtufb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:outbox" /></template>
