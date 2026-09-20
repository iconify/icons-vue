<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1_zr6tbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rss-feed-outline-rounded" /></template>
<style>
.o1_zr6tbx {
  fill: currentColor;
  d: path("M4.357 19.643Q4 19.287 4 18.77t.357-.874t.874-.356t.874.356t.357.874t-.357.874T5.23 20t-.874-.357M18.269 20q-.323 0-.53-.254q-.206-.254-.243-.615q-.16-2.54-1.187-4.769t-2.736-3.935q-1.707-1.708-3.935-2.736T4.869 6.504q-.361-.037-.615-.244Q4 6.054 4 5.73t.248-.533t.566-.18q2.882.16 5.377 1.313q2.496 1.153 4.411 3.068t3.068 4.41t1.313 5.379q.03.317-.18.565t-.534.248m-5.538 0q-.317 0-.527-.245t-.258-.563q-.148-1.436-.74-2.656q-.59-1.22-1.556-2.186t-2.185-1.557t-2.657-.74q-.317-.047-.563-.257T4 11.27q0-.323.248-.527q.248-.203.566-.161q1.728.154 3.23.86t2.654 1.861q1.154 1.154 1.86 2.655t.861 3.23q.042.317-.161.565T12.73 20");
}

</style>
