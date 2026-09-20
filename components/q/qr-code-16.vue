<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka828nvzs.css';
import '../../css/o/o292irb5l.css';
import '../../css/x/xlp4lif3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ka828nvzs"/><path clip-rule="evenodd" class="o292irb5l"/><path class="xlp4lif3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:qr-code-16" /></template>
