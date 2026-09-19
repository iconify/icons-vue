<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcaub0ivy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tcaub0ivy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:plus" /></template>
