<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3_8fkw7e.css';
import '../../css/n/n6sk80bgi.css';
import '../../css/t/ta-kfblvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o3_8fkw7e"/><path clip-rule="evenodd" class="n6sk80bgi"/><path class="ta-kfblvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sunset-bold" /></template>
