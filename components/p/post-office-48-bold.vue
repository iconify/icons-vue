<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjpjj7bux.css';
import '../../css/f/fa8ycbb8q.css';
import '../../css/e/epesvsbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bjpjj7bux"/><path class="fa8ycbb8q"/><path class="epesvsbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:post-office-48-bold" /></template>
