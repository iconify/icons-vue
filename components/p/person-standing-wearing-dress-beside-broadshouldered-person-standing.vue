<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln0831wbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ln0831wbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-standing-wearing-dress-beside-broadshouldered-person-standing" /></template>
