<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp7wmigin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bp7wmigin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:redirect" /></template>
