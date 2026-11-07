<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf5tgeqen.css';
import '../../css/g/g7lf42b8j.css';
import '../../css/k/kjee7xvdg.css';
import '../../css/j/jqlk-kbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf5tgeqen"/><path class="g7lf42b8j"/><path class="kjee7xvdg"/><path class="jqlk-kbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rows-4-bold" /></template>
