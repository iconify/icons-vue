<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk_grnbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:museum-rounded" /></template>
<style>
.uk_grnbua {
  fill: currentColor;
  d: path("M3 21v-1h2V10h-.592q-.272 0-.456-.187q-.183-.188-.183-.457q0-.17.077-.311t.217-.241l7.018-4.927q.217-.142.448-.22t.472-.078t.471.078t.447.22l7.018 4.927q.14.098.217.244t.077.314q0 .272-.183.455t-.456.183H19v10h2v1zm6.472-3.644q.144-.144.144-.356v-4l1.713 2.539q.13.186.305.27q.174.083.366.083t.366-.083q.175-.084.305-.27L14.385 13v4q0 .213.144.356t.356.144t.356-.144t.144-.356v-5.04q0-.195-.133-.328q-.132-.132-.327-.132h-.402q-.111 0-.215.054t-.174.148L12 14.885l-2.104-3.146q-.067-.124-.187-.181q-.118-.058-.272-.058h-.265q-.237 0-.396.16t-.16.398V17q0 .213.143.356q.144.144.357.144t.356-.144");
}

</style>
