<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq5rus7wf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kq5rus7wf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:swift" /></template>
