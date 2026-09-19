<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b__w9xbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b__w9xbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:solaris" /></template>
