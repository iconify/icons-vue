<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfdi-4buo.css';
import '../../css/t/tk4wqivch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qfdi-4buo"/><path class="tk4wqivch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:person-circle-outline" /></template>
