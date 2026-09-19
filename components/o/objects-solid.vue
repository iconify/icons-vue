<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8n9-8bmz.css';
import '../../css/u/ubnymlb9p.css';
import '../../css/t/thrw0jg-j.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 m8n9-8bmz"/><path class="clr-i-solid clr-i-solid-path-2 ubnymlb9p"/><circle class="clr-i-solid clr-i-solid-path-3 thrw0jg-j"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:objects-solid" /></template>
