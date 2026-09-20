<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go81uhbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="go81uhbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:police-officer-with-stop-arm" /></template>
