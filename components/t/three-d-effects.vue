<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhpgzke8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhpgzke8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:three-d-effects" /></template>
