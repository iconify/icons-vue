<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlgswcb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hlgswcb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:vsts" /></template>
