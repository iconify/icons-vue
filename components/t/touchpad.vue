<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dczarkgib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":896};
const content = `<path class="dczarkgib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:touchpad" /></template>
