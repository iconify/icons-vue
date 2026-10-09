<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-75ddbox.css';
import '../../css/g/gva8st1tu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b-75ddbox"/><path class="gva8st1tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:snowboard-48-bold" /></template>
