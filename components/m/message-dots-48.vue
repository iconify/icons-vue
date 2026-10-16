<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me-xmbmth.css';
import '../../css/a/a_pmb6bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="me-xmbmth"/><path class="a_pmb6bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-dots-48" /></template>
