<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0fqn2b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:potted-tree" /></template>
<style>
.l0fqn2b7i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m16.606 6.945l-2.864-3.501q-.676-.825-1.742-.825t-1.742.825L7.395 6.945q-.444.541-.144 1.173q.161.34.438.497l-.813 1.219q-.73 1.095-.109 2.256t1.937 1.16h2.546v1.5H6q-.047 0-.093.006q-.073.009-.143.032q-.071.024-.135.06q-.064.037-.12.085t-.101.107t-.078.124t-.053.137t-.025.145t.004.147l.75 6q.008.067.029.132q.02.065.052.125t.074.114t.093.098t.109.08t.122.059q.063.025.13.037t.135.012h10.5q.068 0 .135-.012t.13-.037q.064-.024.122-.059t.109-.08t.093-.098t.074-.114t.052-.125q.021-.065.029-.132l.75-6q.006-.046.006-.093q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18 14.75h-5.25v-1.5h2.546q1.316 0 1.937-1.16q.621-1.161-.109-2.256l-.813-1.219q.277-.157.438-.497q.3-.632-.143-1.173");
}

</style>
