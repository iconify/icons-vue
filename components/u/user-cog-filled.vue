<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9p861bjm.css';
import '../../css/b/b2y5zk0fk.css';
import '../../css/j/jqs9sql0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9p861bjm"/><path clip-rule="evenodd" class="b2y5zk0fk"/><path class="jqs9sql0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-cog-filled" /></template>
