<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhxi0-bnb.css';
import '../../css/u/u3fkkvb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fhxi0-bnb"/><path class="u3fkkvb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:todo-list" /></template>
