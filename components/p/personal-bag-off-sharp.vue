<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz50rs6xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:personal-bag-off-sharp" /></template>
<style>
.kz50rs6xl {
  fill: currentColor;
  d: path("M12 3.846q.91 0 1.532.64q.622.639.622 1.549v.396q1.66.652 2.753 2.115T18 12v3.573L9.846 7.381V6q0-.904.625-1.529T12 3.846m-.818 1.336q-.336.335-.336.818v.138q.295-.069.577-.104Q11.706 6 12 6t.577.034t.577.105V6q0-.483-.336-.818T12 4.846t-.818.336m9.31 17.11l-3.913-3.908H18V21H6v-9q0-.9.241-1.718q.242-.819.725-1.505L2.86 4.662l.708-.708L21.2 21.584zM10.69 12.5H8.5v1h3.189z");
}

</style>
