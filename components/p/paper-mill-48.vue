<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k23_kvbcb.css';
import '../../css/b/b22tnbb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k23_kvbcb"/><path class="b22tnbb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paper-mill-48" /></template>
