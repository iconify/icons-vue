<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1t2h770l.css';
import '../../css/n/nbyo3qbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z1t2h770l"/><path class="nbyo3qbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:pass-through-16" /></template>
