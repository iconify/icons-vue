<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_ldfj9ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="n_ldfj9ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:picnic-site-11" /></template>
