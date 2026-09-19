<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6tcv5b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1024};
const content = `<path class="l6tcv5b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:shredder" /></template>
