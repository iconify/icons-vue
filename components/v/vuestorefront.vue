<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu5chmb3k.css';
import '../../css/s/s4xleyb5w.css';
import '../../css/l/l1pj3bg-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<rect class="wu5chmb3k"/><path class="s4xleyb5w"/><path class="l1pj3bg-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vuestorefront" /></template>
